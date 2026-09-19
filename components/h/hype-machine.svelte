<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st1q0wxqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":448};
const content = `<path class="st1q0wxqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:hype-machine" {...props}></Icon>
