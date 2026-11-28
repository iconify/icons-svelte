<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmt8y0odu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmt8y0odu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:peace-sign-solid" {...props}></Icon>
