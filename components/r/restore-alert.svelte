<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8egr_bni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8egr_bni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:restore-alert" {...props}></Icon>
