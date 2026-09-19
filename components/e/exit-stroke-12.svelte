<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmdbu6bzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qmdbu6bzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:exit-stroke-12" {...props}></Icon>
