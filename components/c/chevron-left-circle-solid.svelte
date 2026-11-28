<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h868vpbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h868vpbuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-left-circle-solid" {...props}></Icon>
