<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mixyt5cvw.css';
import '../../css/c/c-gfqebqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mixyt5cvw"/><path class="c-gfqebqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rivet-20-bold" {...props}></Icon>
