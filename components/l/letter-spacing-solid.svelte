<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd4144bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd4144bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:letter-spacing-solid" {...props}></Icon>
