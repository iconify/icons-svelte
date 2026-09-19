<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx751ebbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bx751ebbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circleforwardempty" {...props}></Icon>
