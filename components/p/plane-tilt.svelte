<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy4zw-bys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dy4zw-bys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:plane-tilt" {...props}></Icon>
