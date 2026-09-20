<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbjau4brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kbjau4brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:chevron-up-12" {...props}></Icon>
