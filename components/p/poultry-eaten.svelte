<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8v-auhdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u8v-auhdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:poultry-eaten" {...props}></Icon>
