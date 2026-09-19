<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb24vccle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="nb24vccle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:hotdog" {...props}></Icon>
