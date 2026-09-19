<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8z1in5ax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8z1in5ax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:posts" {...props}></Icon>
