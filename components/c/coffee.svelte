<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/borcvuv3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="borcvuv3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:coffee" {...props}></Icon>
