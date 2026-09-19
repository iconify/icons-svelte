<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd_3bbbwk.css';
import '../../css/w/w5hpaebnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zd_3bbbwk"/><path class="w5hpaebnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:cloud-routes" {...props}></Icon>
