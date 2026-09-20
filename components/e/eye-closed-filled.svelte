<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftmluqmfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftmluqmfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:eye-closed-filled" {...props}></Icon>
