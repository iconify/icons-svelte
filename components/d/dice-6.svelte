<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/riq6uybqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="riq6uybqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:dice-6" {...props}></Icon>
