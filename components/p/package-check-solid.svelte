<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq0s9vbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uq0s9vbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:package-check-solid" {...props}></Icon>
