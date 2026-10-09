<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrw5zccqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vrw5zccqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-48-bold" {...props}></Icon>
