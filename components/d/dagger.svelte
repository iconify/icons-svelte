<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz1nshtzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pz1nshtzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:dagger" {...props}></Icon>
