<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s498vrbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s498vrbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:lightbulb" {...props}></Icon>
