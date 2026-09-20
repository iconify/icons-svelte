<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr_jrzbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yr_jrzbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:jump" {...props}></Icon>
