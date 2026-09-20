<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca3d_pk8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ca3d_pk8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:chevron-down" {...props}></Icon>
