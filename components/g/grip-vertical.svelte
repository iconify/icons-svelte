<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1rk4yuft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1rk4yuft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:grip-vertical" {...props}></Icon>
