<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcopg4bsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fcopg4bsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:reservoir-48-bold" {...props}></Icon>
