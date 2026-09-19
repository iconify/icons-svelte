<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk2_vebjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk2_vebjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cloud" {...props}></Icon>
