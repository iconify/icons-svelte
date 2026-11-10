<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klr_i1bss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="klr_i1bss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:noise-wave" {...props}></Icon>
