<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br04frb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="br04frb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:briefcase" {...props}></Icon>
