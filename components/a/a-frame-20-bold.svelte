<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxj-1cpyy.css';
import '../../css/b/bhq-_uklw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hxj-1cpyy"/><path class="bhq-_uklw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:a-frame-20-bold" {...props}></Icon>
