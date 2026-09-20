<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myyz2sbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myyz2sbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:eyebrow-line" {...props}></Icon>
