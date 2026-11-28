<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyx8pkdtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyx8pkdtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:image-wrap-left-solid" {...props}></Icon>
