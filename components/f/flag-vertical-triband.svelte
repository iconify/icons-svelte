<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmxrdnbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hmxrdnbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:flag-vertical-triband" {...props}></Icon>
