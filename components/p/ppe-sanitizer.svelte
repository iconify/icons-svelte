<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7px1cbcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d7px1cbcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ppe-sanitizer" {...props}></Icon>
