<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k26-hfmon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k26-hfmon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:arrow-cursor-1" {...props}></Icon>
