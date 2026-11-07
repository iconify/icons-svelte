<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch5jc2bad.css';
import '../../css/r/rjuy8dl9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ch5jc2bad"/><path class="rjuy8dl9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:close-bold-duotone" {...props}></Icon>
