<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y32oprfqe.css';
import '../../css/o/oquy5qb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y32oprfqe"/><path class="oquy5qb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-range-48" {...props}></Icon>
