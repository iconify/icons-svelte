<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9rzdmy5w.css';
import '../../css/z/zdxcevbat.css';
import '../../css/a/ayyx0bb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j9rzdmy5w"/><path class="zdxcevbat"/><path class="ayyx0bb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lock-keyhole-20-bold" {...props}></Icon>
