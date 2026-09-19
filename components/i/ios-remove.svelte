<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc691boul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hc691boul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-remove" {...props}></Icon>
