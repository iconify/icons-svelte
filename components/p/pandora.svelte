<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1vl4ab-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":488};
const content = `<path class="n1vl4ab-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:pandora" {...props}></Icon>
