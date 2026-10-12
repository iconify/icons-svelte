<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw4sjwb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pw4sjwb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:gap-horizontal-filled" {...props}></Icon>
