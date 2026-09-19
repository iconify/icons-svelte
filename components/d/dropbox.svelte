<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyi2f1bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fyi2f1bps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:dropbox" {...props}></Icon>
