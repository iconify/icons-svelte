<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp3-8kfrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dp3-8kfrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:iphone-x-apps-line" {...props}></Icon>
