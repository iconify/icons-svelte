<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk6mrwbwh.css';
import '../../css/e/ehn9ppzlr.css';
import '../../css/j/jpbcbrl-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tk6mrwbwh"/><path class="ehn9ppzlr"/><path class="jpbcbrl-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:livescript" {...props}></Icon>
