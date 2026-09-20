<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq3mp8b6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oq3mp8b6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bar-chart-fill" {...props}></Icon>
