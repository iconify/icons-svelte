<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3uxvacgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3uxvacgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:chevron-down-square" {...props}></Icon>
