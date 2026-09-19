<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw95eob7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw95eob7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:magnifying-glass-minus" {...props}></Icon>
