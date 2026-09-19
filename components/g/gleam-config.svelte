<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnh7u9f3r.css';
import '../../css/t/t0uauacth.css';
import '../../css/j/jnh3n5bgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gnh7u9f3r"/><path class="t0uauacth"/><path class="jnh3n5bgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:gleam-config" {...props}></Icon>
