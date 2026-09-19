<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru1h04b8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru1h04b8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:queue-list" {...props}></Icon>
