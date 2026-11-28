<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywaekn5oe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywaekn5oe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:earbuds-check" {...props}></Icon>
