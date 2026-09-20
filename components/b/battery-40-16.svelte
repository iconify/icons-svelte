<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i02ogzbva.css';
import '../../css/f/ffaginb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i02ogzbva"/><path clip-rule="evenodd" class="ffaginb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:battery-40-16" {...props}></Icon>
