<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skkkx6ncv.css';
import '../../css/o/ors_3pbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="skkkx6ncv"/><path class="ors_3pbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-reverse-fill-12" {...props}></Icon>
