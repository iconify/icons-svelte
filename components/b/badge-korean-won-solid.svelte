<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trs_dtk_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trs_dtk_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-korean-won-solid" {...props}></Icon>
