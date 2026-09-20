<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcyv-xb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zcyv-xb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:paperless-ngx-dark" {...props}></Icon>
