<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1cbt0mon.css';
import '../../css/f/fx-nsmbzv.css';
import '../../css/l/lnppjcb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j1cbt0mon"/><path class="fx-nsmbzv"/><path class="lnppjcb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:check-valve-20" {...props}></Icon>
