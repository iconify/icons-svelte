<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2-3vzbzw.css';
import '../../css/y/ycekm8byx.css';
import '../../css/v/vwtbn-brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s2-3vzbzw"/><path class="ycekm8byx"/><path class="vwtbn-brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:feather-20" {...props}></Icon>
