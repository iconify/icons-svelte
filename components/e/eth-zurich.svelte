<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr14q2brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":331};
const content = `<path class="kr14q2brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:eth-zurich" {...props}></Icon>
