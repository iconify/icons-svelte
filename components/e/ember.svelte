<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-9dwnblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":488};
const content = `<path class="j-9dwnblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:ember" {...props}></Icon>
