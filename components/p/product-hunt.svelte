<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky74tsb9t.css';
import '../../css/i/iacqrl92w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ky74tsb9t"/><path class="iacqrl92w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:product-hunt" {...props}></Icon>
