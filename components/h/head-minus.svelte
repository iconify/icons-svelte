<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3r324b4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3r324b4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:head-minus" {...props}></Icon>
