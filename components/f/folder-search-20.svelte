<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-w_jtvez.css';
import '../../css/z/z0u0mzbcw.css';
import '../../css/c/cn7q8feaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u-w_jtvez"/><path class="z0u0mzbcw"/><path class="cn7q8feaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-search-20" {...props}></Icon>
