<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5gfqkb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5gfqkb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:eye-off" {...props}></Icon>
