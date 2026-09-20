<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8bfibb-k.css';
import '../../css/b/bkk4-bbas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y8bfibb-k"/><path class="bkk4-bbas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:health-hospital-building-1" {...props}></Icon>
