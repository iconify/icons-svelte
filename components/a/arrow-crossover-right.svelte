<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5wkiebvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="s5wkiebvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-crossover-right" {...props}></Icon>
