<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6jxk8z4w.css';
import '../../css/g/gd0tfm6iv.css';
import '../../css/k/k37vjebfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x6jxk8z4w"/><path class="gd0tfm6iv"/><path class="k37vjebfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grant-20" {...props}></Icon>
