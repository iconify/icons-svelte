<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uogs-ibsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uogs-ibsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:laptop-cloud" {...props}></Icon>
