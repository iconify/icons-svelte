<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9c5bwb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v9c5bwb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:drumsticks-16" {...props}></Icon>
