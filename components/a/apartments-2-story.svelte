<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvc994vvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pvc994vvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:apartments-2-story" {...props}></Icon>
