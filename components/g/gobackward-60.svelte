<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puw4q2wjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="puw4q2wjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:gobackward-60" {...props}></Icon>
