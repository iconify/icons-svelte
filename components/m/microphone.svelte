<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w337psblt.css';
import '../../css/u/u6ht0eb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w337psblt"/><path class="u6ht0eb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:microphone" {...props}></Icon>
