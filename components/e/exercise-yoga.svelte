<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tduyn620x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tduyn620x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:exercise-yoga" {...props}></Icon>
