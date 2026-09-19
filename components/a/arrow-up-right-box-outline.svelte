<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5-g-c5hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k5-g-c5hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-up-right-box-outline" {...props}></Icon>
