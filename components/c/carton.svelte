<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hadc8s2xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hadc8s2xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:carton" {...props}></Icon>
