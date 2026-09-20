<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krotz6bti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krotz6bti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:film-open-star" {...props}></Icon>
