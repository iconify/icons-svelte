<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj2exfbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rj2exfbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:quote-left" {...props}></Icon>
