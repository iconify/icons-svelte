<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz-vsrl_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qz-vsrl_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:iris-scan-solid" {...props}></Icon>
