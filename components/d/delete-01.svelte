<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6hh668-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6hh668-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:delete-01" {...props}></Icon>
