<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p09rohk0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p09rohk0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:open-umbrella" {...props}></Icon>
