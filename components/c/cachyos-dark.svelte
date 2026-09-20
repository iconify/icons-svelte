<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no_cqmfti.css';
import '../../css/c/cmsj9noho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="no_cqmfti"/><path class="cmsj9noho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cachyos-dark" {...props}></Icon>
