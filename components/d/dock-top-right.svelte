<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfjb5jbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfjb5jbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-top-right" {...props}></Icon>
