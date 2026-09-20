<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en0_7acrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="en0_7acrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:docker" {...props}></Icon>
