<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq-tdwb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qq-tdwb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevrons-left-right-48" {...props}></Icon>
