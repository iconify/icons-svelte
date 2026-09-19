<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj-g3nbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wj-g3nbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:arrow-alt-circle-up" {...props}></Icon>
