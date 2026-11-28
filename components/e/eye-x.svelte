<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz7g6o3_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sz7g6o3_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:eye-x" {...props}></Icon>
