<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7n36ms-b.css';
import '../../css/a/a1wp-ubtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x7n36ms-b"/><path class="a1wp-ubtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-open-48-bold" {...props}></Icon>
