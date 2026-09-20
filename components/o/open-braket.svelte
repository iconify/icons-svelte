<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am4ytlbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="am4ytlbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:open-braket" {...props}></Icon>
