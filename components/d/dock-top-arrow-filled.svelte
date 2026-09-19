<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0guk_b0a.css';
import '../../css/c/citsypb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0guk_b0a"/><path class="citsypb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-top-arrow-filled" {...props}></Icon>
