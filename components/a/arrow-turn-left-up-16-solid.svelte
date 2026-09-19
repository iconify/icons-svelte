<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub05ksbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ub05ksbjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-left-up-16-solid" {...props}></Icon>
