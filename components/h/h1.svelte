<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm-5ndbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fm-5ndbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:h1" {...props}></Icon>
