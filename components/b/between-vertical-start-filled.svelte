<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5eyj2bfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5eyj2bfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:between-vertical-start-filled" {...props}></Icon>
