<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-pkev7bs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-pkev7bs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:namecheap" {...props}></Icon>
