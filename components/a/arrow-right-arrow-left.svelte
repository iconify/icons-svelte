<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0j17oawz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0j17oawz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:arrow-right-arrow-left" {...props}></Icon>
