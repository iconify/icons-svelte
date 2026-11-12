<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6-lcumwc.css';
import '../../css/l/lvu082s3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j6-lcumwc"/><path class="lvu082s3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:material-for-mkdocs-light" {...props}></Icon>
