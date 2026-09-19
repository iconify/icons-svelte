<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg5b6wann.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tg5b6wann"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chart-line" {...props}></Icon>
