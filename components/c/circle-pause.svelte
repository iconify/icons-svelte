<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo95jm1am.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bo95jm1am"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:circle-pause" {...props}></Icon>
