<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vug20nb6u.css';
import '../../css/c/cfm66s3uf.css';
import '../../css/b/bfjbb2-nr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vug20nb6u"/><path class="cfm66s3uf"/><path class="bfjbb2-nr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rhel-dark" {...props}></Icon>
