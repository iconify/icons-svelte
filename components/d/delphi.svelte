<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igvua1b9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="igvua1b9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:delphi" {...props}></Icon>
