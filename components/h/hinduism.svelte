<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_gxueo7c.css';
import '../../css/p/p6eql6bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_gxueo7c st0"/><path class="p6eql6bly st0"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:hinduism" {...props}></Icon>
