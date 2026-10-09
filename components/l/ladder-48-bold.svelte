<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klcw8eg5x.css';
import '../../css/n/nbve-mbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="klcw8eg5x"/><path class="nbve-mbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ladder-48-bold" {...props}></Icon>
