<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5v8cfb5j.css';
import '../../css/g/gd--6wbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="f5v8cfb5j"/><path class="gd--6wbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:gatling-wordmark" {...props}></Icon>
