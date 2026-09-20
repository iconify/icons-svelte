<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2m6l6bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f2m6l6bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-sledding-downhill" {...props}></Icon>
