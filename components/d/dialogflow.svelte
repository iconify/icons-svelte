<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhrg1ac9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="yhrg1ac9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:dialogflow" {...props}></Icon>
