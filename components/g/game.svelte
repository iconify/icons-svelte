<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqv1ecbnn.css';
import '../../css/d/df0l6dbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="sqv1ecbnn"/><path class="df0l6dbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:game" {...props}></Icon>
