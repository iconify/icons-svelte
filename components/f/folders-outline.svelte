<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfr9e0tvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dfr9e0tvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:folders-outline" {...props}></Icon>
