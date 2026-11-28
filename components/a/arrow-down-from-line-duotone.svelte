<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klt794f4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klt794f4c primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-down-from-line-duotone" {...props}></Icon>
