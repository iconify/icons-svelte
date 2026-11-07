<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywnaxmbog.css';
import '../../css/z/zaqxs8bvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywnaxmbog"/><path clip-rule="evenodd" class="zaqxs8bvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:meditation-bold" {...props}></Icon>
