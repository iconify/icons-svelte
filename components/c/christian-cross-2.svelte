<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgib-pbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qgib-pbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:christian-cross-2" {...props}></Icon>
