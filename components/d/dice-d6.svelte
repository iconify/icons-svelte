<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg9evwbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="sg9evwbyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:dice-d6" {...props}></Icon>
