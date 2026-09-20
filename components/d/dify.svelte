<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf_mwkbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hf_mwkbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:dify" {...props}></Icon>
