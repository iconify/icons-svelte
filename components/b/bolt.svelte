<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg6mswtmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="dg6mswtmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:bolt" {...props}></Icon>
