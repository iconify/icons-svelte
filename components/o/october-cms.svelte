<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i07yc3wsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i07yc3wsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:october-cms" {...props}></Icon>
