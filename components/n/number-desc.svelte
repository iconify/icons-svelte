<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-734_b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="k-734_b6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:number-desc" {...props}></Icon>
