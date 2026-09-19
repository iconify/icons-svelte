<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac6pctzqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ac6pctzqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:minus" {...props}></Icon>
