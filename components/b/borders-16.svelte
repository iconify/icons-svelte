<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qndn4-bth.css';
import '../../css/j/jodh5db0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qndn4-bth"/><path clip-rule="evenodd" class="jodh5db0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:borders-16" {...props}></Icon>
