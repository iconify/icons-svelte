<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb9fn2b6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rb9fn2b6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:layers-minus-filled" {...props}></Icon>
