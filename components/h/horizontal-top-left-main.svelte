<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtzp2h9ju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtzp2h9ju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:horizontal-top-left-main" {...props}></Icon>
