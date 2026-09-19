<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uibprsbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":384};
const content = `<path class="uibprsbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:mail-send" {...props}></Icon>
