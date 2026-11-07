<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdvbgrb8q.css';
import '../../css/c/cq7nq2bzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdvbgrb8q"/><path class="cq7nq2bzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:laptop-3-bold-duotone" {...props}></Icon>
