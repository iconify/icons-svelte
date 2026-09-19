<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khqx3jp6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khqx3jp6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:paper-bag-filled" {...props}></Icon>
