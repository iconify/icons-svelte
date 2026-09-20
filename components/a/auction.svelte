<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnr5_bciz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnr5_bciz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:auction" {...props}></Icon>
