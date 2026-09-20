<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t95osacvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t95osacvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nutalert-dark" {...props}></Icon>
