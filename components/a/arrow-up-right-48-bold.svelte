<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbj7ts9zy.css';
import '../../css/e/efdwgfbme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rbj7ts9zy"/><path class="efdwgfbme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-up-right-48-bold" {...props}></Icon>
