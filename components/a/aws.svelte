<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpj9x5mgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpj9x5mgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:aws" {...props}></Icon>
