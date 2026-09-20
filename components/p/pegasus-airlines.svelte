<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_h1m2mak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_h1m2mak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pegasus-airlines" {...props}></Icon>
