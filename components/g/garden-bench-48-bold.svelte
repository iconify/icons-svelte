<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehlerpbsz.css';
import '../../css/f/fwo9yhojg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ehlerpbsz"/><path class="fwo9yhojg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:garden-bench-48-bold" {...props}></Icon>
