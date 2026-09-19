<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l69rg0b1y.css';
import '../../css/f/f6ypmdp8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l69rg0b1y"/><path class="f6ypmdp8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:gradient-filled" {...props}></Icon>
