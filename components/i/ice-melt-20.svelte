<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzhy174bn.css';
import '../../css/t/t70ittbnx.css';
import '../../css/c/c6hof6utt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dzhy174bn"/><path class="t70ittbnx"/><path class="c6hof6utt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ice-melt-20" {...props}></Icon>
