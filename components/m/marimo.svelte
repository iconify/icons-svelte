<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if0nh-buo.css';
import '../../css/b/b57rxsbat.css';
import '../../css/i/ivod1rbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":139.149,"height":111.25};
const content = `<path class="if0nh-buo"/><path class="b57rxsbat"/><path class="ivod1rbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:marimo" {...props}></Icon>
