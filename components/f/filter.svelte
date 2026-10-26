<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5j7fss2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r5j7fss2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:filter" {...props}></Icon>
