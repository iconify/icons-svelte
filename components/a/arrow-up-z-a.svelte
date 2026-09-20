<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbz6_zhjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbz6_zhjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-up-z-a" {...props}></Icon>
