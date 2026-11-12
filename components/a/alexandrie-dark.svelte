<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obng8298b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="obng8298b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alexandrie-dark" {...props}></Icon>
