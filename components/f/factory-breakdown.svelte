<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zytnknbqy.css';
import '../../css/h/hxrdmob8v.css';
import '../../css/j/j1_yf7_6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zytnknbqy"/><path class="hxrdmob8v"/><path class="j1_yf7_6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:factory-breakdown" {...props}></Icon>
