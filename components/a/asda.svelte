<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op-b1jbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="op-b1jbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:asda" {...props}></Icon>
