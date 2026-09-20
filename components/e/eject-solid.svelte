<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckhw15x6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckhw15x6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:eject-solid" {...props}></Icon>
