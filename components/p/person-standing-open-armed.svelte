<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r34x9s4nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r34x9s4nm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-standing-open-armed" {...props}></Icon>
