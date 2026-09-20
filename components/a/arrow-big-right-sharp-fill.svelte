<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih_mnsbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ih_mnsbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-big-right-sharp-fill" {...props}></Icon>
