<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to33eh6vt.css';
import '../../css/t/t6ndzsb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="to33eh6vt"/><path class="t6ndzsb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:envelopes" {...props}></Icon>
