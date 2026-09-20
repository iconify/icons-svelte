<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuw7zub5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kuw7zub5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrow-left-expressive" {...props}></Icon>
