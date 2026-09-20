<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq-5qrh1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="rq-5qrh1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-coffee-shop" {...props}></Icon>
