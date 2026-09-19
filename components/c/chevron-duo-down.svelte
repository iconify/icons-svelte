<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wax1c9b0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wax1c9b0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chevron-duo-down" {...props}></Icon>
