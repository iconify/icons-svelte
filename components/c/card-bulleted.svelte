<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-bkw3zgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-bkw3zgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:card-bulleted" {...props}></Icon>
