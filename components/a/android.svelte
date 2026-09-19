<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2n6oj1vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="e2n6oj1vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:android" {...props}></Icon>
