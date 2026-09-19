<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm41t744z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":488};
const content = `<path class="fm41t744z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:ming" {...props}></Icon>
