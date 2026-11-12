<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adpj7nbwk.css';
import '../../css/h/h7s3e_b2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="adpj7nbwk"/><path class="h7s3e_b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hawser" {...props}></Icon>
