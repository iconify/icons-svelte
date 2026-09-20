<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw_qgvbot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bw_qgvbot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pin-hospital" {...props}></Icon>
