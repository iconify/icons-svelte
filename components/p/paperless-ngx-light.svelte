<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbb4g5h2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zbb4g5h2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:paperless-ngx-light" {...props}></Icon>
