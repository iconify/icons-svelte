<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn4a-muwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mn4a-muwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-turn-up-right" {...props}></Icon>
