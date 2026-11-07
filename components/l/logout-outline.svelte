<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl4lbdb9f.css';
import '../../css/g/g1x_1bbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zl4lbdb9f"/><path class="g1x_1bbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:logout-outline" {...props}></Icon>
