<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj2_uqniq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zj2_uqniq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:keyhole-circle" {...props}></Icon>
