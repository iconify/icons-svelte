<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by5-f4bvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="by5-f4bvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:currency-filled" {...props}></Icon>
