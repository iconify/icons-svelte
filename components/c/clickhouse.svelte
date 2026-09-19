<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohc817x8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ohc817x8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:clickhouse" {...props}></Icon>
