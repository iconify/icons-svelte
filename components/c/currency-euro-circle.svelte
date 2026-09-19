<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7l8-o35n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7l8-o35n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:currency-euro-circle" {...props}></Icon>
