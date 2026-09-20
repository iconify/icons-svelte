<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck9oiac6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ck9oiac6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:hazelnut-with-leaves" {...props}></Icon>
