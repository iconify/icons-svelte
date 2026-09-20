<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk8o4mlup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pk8o4mlup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:door-closed" {...props}></Icon>
