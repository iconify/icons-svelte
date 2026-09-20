<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwxn1vbpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwxn1vbpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:align-bottom-solid" {...props}></Icon>
