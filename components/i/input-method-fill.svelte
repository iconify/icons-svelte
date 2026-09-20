<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8x0qptyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8x0qptyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:input-method-fill" {...props}></Icon>
