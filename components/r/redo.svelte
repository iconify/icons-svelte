<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak8avv8mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ak8avv8mp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:redo" {...props}></Icon>
