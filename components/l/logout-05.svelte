<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze52d2b6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ze52d2b6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:logout-05" {...props}></Icon>
