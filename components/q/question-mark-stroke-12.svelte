<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovsyq3krw.css';
import '../../css/r/r4-qnybet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ovsyq3krw"/><circle class="r4-qnybet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:question-mark-stroke-12" {...props}></Icon>
