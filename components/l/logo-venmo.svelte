<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-q2yr28x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j-q2yr28x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-venmo" {...props}></Icon>
