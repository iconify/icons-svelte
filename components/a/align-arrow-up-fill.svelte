<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of3fd8b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="of3fd8b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-arrow-up-fill" {...props}></Icon>
