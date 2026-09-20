<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9nndzbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b9nndzbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-tower-3-level" {...props}></Icon>
