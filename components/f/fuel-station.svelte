<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md372acym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="md372acym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:fuel-station" {...props}></Icon>
