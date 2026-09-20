<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd5w4cckj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kd5w4cckj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hiking-round-outline" {...props}></Icon>
