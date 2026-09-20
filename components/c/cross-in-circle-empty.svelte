<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z929_bb-t.css';
import '../../css/v/v_12yfv8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z929_bb-t"/><path class="v_12yfv8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:cross-in-circle-empty" {...props}></Icon>
