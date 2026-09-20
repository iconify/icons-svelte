<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q61l43pac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q61l43pac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:lunokhod" {...props}></Icon>
