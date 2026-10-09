<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7tynrbzb.css';
import '../../css/b/bqqcw45gt.css';
import '../../css/c/clko2h42t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x7tynrbzb"/><path class="bqqcw45gt"/><path class="clko2h42t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:butterfly-20" {...props}></Icon>
