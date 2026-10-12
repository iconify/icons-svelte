<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/big4id24i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="big4id24i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:popsicle-filled" {...props}></Icon>
