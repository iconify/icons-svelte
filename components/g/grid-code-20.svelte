<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezhonm73e.css';
import '../../css/k/k2af-4bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ezhonm73e"/><path class="k2af-4bql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grid-code-20" {...props}></Icon>
