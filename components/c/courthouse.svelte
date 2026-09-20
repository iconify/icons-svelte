<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arhog_kvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="arhog_kvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:courthouse" {...props}></Icon>
