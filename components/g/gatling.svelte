<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yiufr8b9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="yiufr8b9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:gatling" {...props}></Icon>
