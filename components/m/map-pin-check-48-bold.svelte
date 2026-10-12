<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijtm4crnn.css';
import '../../css/a/afxexlctq.css';
import '../../css/y/y9mg2tbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ijtm4crnn"/><path class="afxexlctq"/><path class="y9mg2tbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-pin-check-48-bold" {...props}></Icon>
