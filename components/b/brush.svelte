<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en5h58b5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="en5h58b5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:brush" {...props}></Icon>
