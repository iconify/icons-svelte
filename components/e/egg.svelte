<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3i7uqbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l3i7uqbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:egg" {...props}></Icon>
