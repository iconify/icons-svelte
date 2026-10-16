<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkzmacc8l.css';
import '../../css/a/a4qgedb8h.css';
import '../../css/t/ta45wzagz.css';
import '../../css/y/yfoxxnbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xkzmacc8l"/><path class="a4qgedb8h"/><path class="ta45wzagz"/><path class="yfoxxnbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:parliament-20-bold" {...props}></Icon>
