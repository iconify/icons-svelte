<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebyvdvb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebyvdvb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chevron-left" {...props}></Icon>
