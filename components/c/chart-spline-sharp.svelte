<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5nwv8b5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5nwv8b5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-spline-sharp" {...props}></Icon>
