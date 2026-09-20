<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd7m4fbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qd7m4fbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:heart-off" {...props}></Icon>
