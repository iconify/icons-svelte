<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm1k1rblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lm1k1rblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:online-medical-service-monitor-solid" {...props}></Icon>
