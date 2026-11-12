<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbiaeacws.css';
import '../../css/h/hjy0wjyzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mbiaeacws"/><path class="hjy0wjyzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fileflows-forge-dark" {...props}></Icon>
