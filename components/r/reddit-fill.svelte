<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9ny_92rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9ny_92rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:reddit-fill" {...props}></Icon>
