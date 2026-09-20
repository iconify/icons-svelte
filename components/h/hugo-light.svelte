<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcdb8rbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qcdb8rbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hugo-light" {...props}></Icon>
