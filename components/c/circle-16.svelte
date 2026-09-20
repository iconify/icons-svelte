<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvgij0b_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xvgij0b_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:circle-16" {...props}></Icon>
