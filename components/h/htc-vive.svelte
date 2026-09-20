<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw8sdm1be.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aw8sdm1be"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:htc-vive" {...props}></Icon>
