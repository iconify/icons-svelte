<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xguz53ivc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xguz53ivc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:info-variant-box" {...props}></Icon>
