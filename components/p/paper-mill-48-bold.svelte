<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwjrqmb9j.css';
import '../../css/c/casff0y7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mwjrqmb9j"/><path class="casff0y7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paper-mill-48-bold" {...props}></Icon>
