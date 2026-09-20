<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h10vd1ynh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h10vd1ynh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-down-dashed" {...props}></Icon>
