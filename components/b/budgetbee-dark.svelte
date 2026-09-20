<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uthnkib2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uthnkib2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:budgetbee-dark" {...props}></Icon>
