<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld-u1jbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ld-u1jbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:goal" {...props}></Icon>
