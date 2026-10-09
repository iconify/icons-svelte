<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glxb9obxa.css';
import '../../css/r/rbj7ts9zy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="glxb9obxa"/><path class="rbj7ts9zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:close-48-bold" {...props}></Icon>
