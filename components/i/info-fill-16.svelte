<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-ccc-byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v-ccc-byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:info-fill-16" {...props}></Icon>
