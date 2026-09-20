<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_i8e7bst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_i8e7bst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-right-bottom" {...props}></Icon>
