<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlcufkbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="mlcufkbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:ram" {...props}></Icon>
