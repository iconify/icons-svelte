<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oveujm7yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oveujm7yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-radio" {...props}></Icon>
