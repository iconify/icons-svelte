<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml2y4kw_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ml2y4kw_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-bar-stacked-sharp" {...props}></Icon>
