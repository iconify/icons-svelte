<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avtm5wdul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avtm5wdul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grid-3x3-sharp" {...props}></Icon>
