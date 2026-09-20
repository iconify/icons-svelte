<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyctoj_di.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lyctoj_di"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:marketplace" {...props}></Icon>
