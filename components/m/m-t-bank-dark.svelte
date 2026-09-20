<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwbp4q8dw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fwbp4q8dw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:m-t-bank-dark" {...props}></Icon>
