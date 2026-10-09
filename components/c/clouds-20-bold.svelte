<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze-vj538g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ze-vj538g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clouds-20-bold" {...props}></Icon>
