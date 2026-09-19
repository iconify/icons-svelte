<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftuj4zbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ftuj4zbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nginx" {...props}></Icon>
