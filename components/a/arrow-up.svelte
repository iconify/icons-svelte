<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w29qddbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w29qddbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:arrow-up" {...props}></Icon>
