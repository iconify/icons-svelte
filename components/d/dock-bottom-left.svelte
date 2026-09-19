<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9sq7n4kc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9sq7n4kc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-bottom-left" {...props}></Icon>
