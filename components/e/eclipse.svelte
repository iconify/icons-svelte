<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbxx3n40q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="wbxx3n40q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:eclipse" {...props}></Icon>
