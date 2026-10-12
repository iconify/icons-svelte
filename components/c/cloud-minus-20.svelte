<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjuk3kbct.css';
import '../../css/g/gr80gyb-f.css';
import '../../css/a/a--uzxbtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hjuk3kbct"/><path class="gr80gyb-f"/><path class="a--uzxbtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-minus-20" {...props}></Icon>
