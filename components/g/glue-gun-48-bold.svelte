<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmedpvb3p.css';
import '../../css/j/je85er4yr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kmedpvb3p"/><path class="je85er4yr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:glue-gun-48-bold" {...props}></Icon>
