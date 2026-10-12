<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi3ptw9oo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gi3ptw9oo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:columns-4-filled" {...props}></Icon>
