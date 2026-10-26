<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acydh6b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="acydh6b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:call" {...props}></Icon>
