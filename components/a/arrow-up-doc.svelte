<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk6o67b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="pk6o67b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-up-doc" {...props}></Icon>
