<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig9ix3tip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ig9ix3tip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-down-from-line" {...props}></Icon>
