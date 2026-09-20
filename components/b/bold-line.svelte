<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smeqgmelp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smeqgmelp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:bold-line" {...props}></Icon>
