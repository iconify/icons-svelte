<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1wq6303o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1wq6303o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:air-filter" {...props}></Icon>
