<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh6ezcbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vh6ezcbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-ccmp-small-filled" {...props}></Icon>
