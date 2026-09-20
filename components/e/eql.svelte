<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9q0xo4ir.css';
import '../../css/g/gnncr1dzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q9q0xo4ir"/><path class="gnncr1dzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:eql" {...props}></Icon>
