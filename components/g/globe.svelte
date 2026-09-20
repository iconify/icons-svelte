<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qedv1cb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qedv1cb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:globe" {...props}></Icon>
