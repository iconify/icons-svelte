<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl-q1cbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="yl-q1cbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:location-slash-fill" {...props}></Icon>
