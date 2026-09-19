<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkw265b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="kkw265b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:angularjs-wordmark" {...props}></Icon>
