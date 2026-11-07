<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy2y5qfqd.css';
import '../../css/z/zxk5nz2lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qy2y5qfqd"/><path class="zxk5nz2lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bookmark-x-bold-duotone" {...props}></Icon>
