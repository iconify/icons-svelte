<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjb-r5bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="pjb-r5bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:arrow-down" {...props}></Icon>
