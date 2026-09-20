<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7xq-85yk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7xq-85yk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ceiling-light-outline" {...props}></Icon>
