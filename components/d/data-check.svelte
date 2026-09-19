<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3dgaob_q.css';
import '../../css/x/xx4upobit.css';
import '../../css/b/b6ueueufz.css';
import '../../css/n/nvorv_bgg.css';
import '../../css/e/e7e7wmxcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c3dgaob_q"/><circle class="xx4upobit"/><circle class="b6ueueufz"/><circle class="nvorv_bgg"/><path class="e7e7wmxcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-check" {...props}></Icon>
