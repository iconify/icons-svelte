<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly9882b_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ly9882b_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chevrons-to-axis-dashed-horizontal" {...props}></Icon>
