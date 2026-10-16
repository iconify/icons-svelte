<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6mpagzxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1080,"height":1080};
const content = `<path class="k6mpagzxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:plunk" {...props}></Icon>
