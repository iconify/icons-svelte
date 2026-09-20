<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqy9krt7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqy9krt7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rewind-back-bold" {...props}></Icon>
