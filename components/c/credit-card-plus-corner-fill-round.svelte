<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qipb8obgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qipb8obgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:credit-card-plus-corner-fill-round" {...props}></Icon>
