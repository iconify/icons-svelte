<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxud8ntgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxud8ntgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:betterdiscord" {...props}></Icon>
