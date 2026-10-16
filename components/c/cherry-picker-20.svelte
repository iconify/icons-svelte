<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvfa_-8wt.css';
import '../../css/q/qlwn4rb9s.css';
import '../../css/y/y1kkhac6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vvfa_-8wt"/><path class="qlwn4rb9s"/><path class="y1kkhac6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cherry-picker-20" {...props}></Icon>
