<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe3wgdbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qe3wgdbtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:bell" {...props}></Icon>
