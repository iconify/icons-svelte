<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eonk5dneh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":895,"height":1025};
const content = `<path class="eonk5dneh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:phorum" {...props}></Icon>
