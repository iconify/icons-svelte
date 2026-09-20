<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im0dkrbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="im0dkrbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-left5" {...props}></Icon>
