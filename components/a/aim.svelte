<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow134470u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":488};
const content = `<path class="ow134470u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:aim" {...props}></Icon>
