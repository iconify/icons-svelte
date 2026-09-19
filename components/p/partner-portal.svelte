<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7sr6ubzr.css';
import '../../css/z/zg_xfubcu.css';
import '../../css/z/z98wavxds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7sr6ubzr"/><path class="zg_xfubcu"/><path class="z98wavxds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:partner-portal" {...props}></Icon>
