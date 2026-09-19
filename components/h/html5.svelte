<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to-wjbbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="to-wjbbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:html5" {...props}></Icon>
