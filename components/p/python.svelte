<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/berfx5bid.css';
import '../../css/x/xvhi1u9pz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="berfx5bid"/><path class="xvhi1u9pz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:python" {...props}></Icon>
