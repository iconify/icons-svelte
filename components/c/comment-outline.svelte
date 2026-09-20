<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7eiit0ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7eiit0ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comment-outline" {...props}></Icon>
