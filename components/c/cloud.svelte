<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oizp8mura.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oizp8mura"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:cloud" {...props}></Icon>
