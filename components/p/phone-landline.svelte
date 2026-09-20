<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0v05y64m.css';
import '../../css/a/adgg27x9x.css';
import '../../css/t/t3url24-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r0v05y64m"/><path class="adgg27x9x"/><path class="t3url24-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:phone-landline" {...props}></Icon>
