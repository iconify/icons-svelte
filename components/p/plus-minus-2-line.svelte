<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzwie_b2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzwie_b2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:plus-minus-2-line" {...props}></Icon>
