<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of51ge8mz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="of51ge8mz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-pin" {...props}></Icon>
