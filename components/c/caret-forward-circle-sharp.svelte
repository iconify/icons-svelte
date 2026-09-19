<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv-wanbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iv-wanbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:caret-forward-circle-sharp" {...props}></Icon>
