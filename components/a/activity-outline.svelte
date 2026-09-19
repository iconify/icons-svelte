<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr76i0hug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rr76i0hug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:activity-outline" {...props}></Icon>
