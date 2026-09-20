<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6q28_uum.css';
import '../../css/q/q2kzgfbfr.css';
import '../../css/n/nyo26bcbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b6q28_uum"/><path class="q2kzgfbfr"/><path class="nyo26bcbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:file-portal-dark" {...props}></Icon>
