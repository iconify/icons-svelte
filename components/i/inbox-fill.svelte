<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdpxn5qhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdpxn5qhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:inbox-fill" {...props}></Icon>
