<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu44ccbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lu44ccbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:flask-outline" {...props}></Icon>
