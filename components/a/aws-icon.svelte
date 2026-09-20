<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7vrkybqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":10,"left":-1,"top":13};
const content = `<path class="i7vrkybqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:aws-icon" {...props}></Icon>
