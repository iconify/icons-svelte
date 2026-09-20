<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/genf906_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="genf906_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:night-moon-begin" {...props}></Icon>
