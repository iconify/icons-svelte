<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvupsel1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qvupsel1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-hourglass" {...props}></Icon>
