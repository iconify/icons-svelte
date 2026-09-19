<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caw1diebi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="caw1diebi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:egg" {...props}></Icon>
