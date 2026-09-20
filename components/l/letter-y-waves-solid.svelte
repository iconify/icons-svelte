<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtb38qbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtb38qbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-y-waves-solid" {...props}></Icon>
