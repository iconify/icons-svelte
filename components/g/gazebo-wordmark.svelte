<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8tz3qzqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="k8tz3qzqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:gazebo-wordmark" {...props}></Icon>
