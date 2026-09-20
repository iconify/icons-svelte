<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdc_khbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdc_khbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:angle-left" {...props}></Icon>
