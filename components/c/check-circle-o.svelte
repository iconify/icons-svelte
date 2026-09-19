<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zviov1bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zviov1bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:check-circle-o" {...props}></Icon>
