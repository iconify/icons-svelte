<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1mqx4hvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t1mqx4hvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:balloon" {...props}></Icon>
