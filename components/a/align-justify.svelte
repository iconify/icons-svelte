<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av9tczb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av9tczb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:align-justify" {...props}></Icon>
