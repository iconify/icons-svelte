<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9v855hut.css';
import '../../css/m/mynyiognu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c9v855hut"/><path class="mynyiognu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:marker-hydro-48" {...props}></Icon>
