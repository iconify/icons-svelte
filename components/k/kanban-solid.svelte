<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwyge7-ou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lwyge7-ou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:kanban-solid" {...props}></Icon>
