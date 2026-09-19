<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h016k5e5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h016k5e5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-down-2-light" {...props}></Icon>
