<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edo1bac0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="edo1bac0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:lowered-kerb" {...props}></Icon>
