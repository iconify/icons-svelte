<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8ky2vdcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8ky2vdcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-check-solid" {...props}></Icon>
