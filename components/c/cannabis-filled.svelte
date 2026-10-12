<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziweoj99g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ziweoj99g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cannabis-filled" {...props}></Icon>
