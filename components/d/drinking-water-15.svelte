<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saq9jgb9j.css';
import '../../css/q/qyfnmsb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="saq9jgb9j"/><path class="qyfnmsb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:drinking-water-15" {...props}></Icon>
