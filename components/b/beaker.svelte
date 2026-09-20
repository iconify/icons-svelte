<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahvp5t92z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahvp5t92z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:beaker" {...props}></Icon>
