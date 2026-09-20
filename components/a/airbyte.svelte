<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxfp7ac1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxfp7ac1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:airbyte" {...props}></Icon>
