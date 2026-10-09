<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy5juccjo.css';
import '../../css/m/myqgc4b0y.css';
import '../../css/x/x3s8noxxt.css';
import '../../css/b/bmcev9bhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gy5juccjo"/><path class="myqgc4b0y"/><path class="x3s8noxxt"/><path class="bmcev9bhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:atom-20-bold" {...props}></Icon>
