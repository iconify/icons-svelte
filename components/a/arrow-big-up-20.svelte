<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivydbo0ez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ivydbo0ez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-big-up-20" {...props}></Icon>
