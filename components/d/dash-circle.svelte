<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5gqdlb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p5gqdlb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:dash-circle" {...props}></Icon>
