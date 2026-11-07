<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-vj9jbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-vj9jbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dumbbell-linear" {...props}></Icon>
