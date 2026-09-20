<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxg--r65y.css';
import '../../css/a/acs4rfber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxg--r65y"/><path class="acs4rfber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:oxt" {...props}></Icon>
