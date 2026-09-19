<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asyv5fbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="asyv5fbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-undo-circle" {...props}></Icon>
