<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs0r5lbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vs0r5lbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-at" {...props}></Icon>
