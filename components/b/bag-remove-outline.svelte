<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnc5a8hke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qnc5a8hke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:bag-remove-outline" {...props}></Icon>
