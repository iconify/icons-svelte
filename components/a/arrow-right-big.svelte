<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrusicbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrusicbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-right-big" {...props}></Icon>
