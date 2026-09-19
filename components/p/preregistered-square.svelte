<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1mc5lbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="a1mc5lbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:preregistered-square" {...props}></Icon>
