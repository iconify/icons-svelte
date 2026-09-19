<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m00omrtku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m00omrtku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:arrow-right-down" {...props}></Icon>
