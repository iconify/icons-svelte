<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj3q2bi4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nj3q2bi4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:kaios" {...props}></Icon>
