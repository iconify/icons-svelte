<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-rcmwban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o-rcmwban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:free-isp-light" {...props}></Icon>
