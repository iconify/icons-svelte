<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-l-y7baz.css';
import '../../css/c/cnp57_zxn.css';
import '../../css/j/jlvwd6bkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k-l-y7baz"/><path class="cnp57_zxn"/><path class="jlvwd6bkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:archive-20-bold" {...props}></Icon>
