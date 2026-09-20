<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtyn5_b3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gtyn5_b3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-outline" {...props}></Icon>
