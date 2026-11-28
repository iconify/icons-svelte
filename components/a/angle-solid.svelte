<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afu_zwhke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afu_zwhke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:angle-solid" {...props}></Icon>
