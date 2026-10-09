<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq-4s2b4h.css';
import '../../css/k/ko8go1bco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vq-4s2b4h"/><path class="ko8go1bco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pickaxe-20" {...props}></Icon>
