<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njsbplffl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="njsbplffl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:home-assistant-dark" {...props}></Icon>
