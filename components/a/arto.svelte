<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfswnh5af.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":488};
const content = `<path class="cfswnh5af"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:arto" {...props}></Icon>
