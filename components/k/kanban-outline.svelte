<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_s7jsbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z_s7jsbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:kanban-outline" {...props}></Icon>
