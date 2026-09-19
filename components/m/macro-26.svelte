<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewz6b-n0l.css';
import '../../css/x/x2s3-fbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="ewz6b-n0l"/><path class="x2s3-fbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:macro-26" {...props}></Icon>
