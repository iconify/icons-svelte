<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-072_yla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h-072_yla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:logout-half-circle" {...props}></Icon>
