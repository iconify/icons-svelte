<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijp3onb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijp3onb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:money-euro-circle-fill" {...props}></Icon>
