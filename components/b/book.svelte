<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t22i2pu7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="t22i2pu7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:book" {...props}></Icon>
