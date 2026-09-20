<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azsfvfb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azsfvfb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-chevrons-up-sharp-fill" {...props}></Icon>
