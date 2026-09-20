<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqn71vbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqn71vbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:envoy-proxy" {...props}></Icon>
