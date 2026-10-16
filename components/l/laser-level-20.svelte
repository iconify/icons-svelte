<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg0u5tbyf.css';
import '../../css/q/qnjki0hlv.css';
import '../../css/j/jf1_jq5jw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zg0u5tbyf"/><path class="qnjki0hlv"/><path class="jf1_jq5jw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:laser-level-20" {...props}></Icon>
