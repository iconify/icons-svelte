<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju9wp0ymi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ju9wp0ymi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:location-pause" {...props}></Icon>
