<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pglrz1amb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pglrz1amb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-turn-down-left" {...props}></Icon>
