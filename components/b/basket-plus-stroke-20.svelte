<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvt-fvj0a.css';
import '../../css/h/hxwzeibnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pvt-fvj0a"/><path class="hxwzeibnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:basket-plus-stroke-20" {...props}></Icon>
