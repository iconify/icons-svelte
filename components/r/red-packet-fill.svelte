<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da49kcg0i.css';
import '../../css/x/xdwstclco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="da49kcg0i"/><path class="xdwstclco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:red-packet-fill" {...props}></Icon>
