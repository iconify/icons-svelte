<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mobv6wb_v.css';
import '../../css/j/jr13wwetb.css';
import '../../css/g/gvknz8zvu.css';
import '../../css/a/a-4ra4bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mobv6wb_v"/><path class="jr13wwetb"/><path class="gvknz8zvu"/><path class="a-4ra4bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:instagram-alt" {...props}></Icon>
