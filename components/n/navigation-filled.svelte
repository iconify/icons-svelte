<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw8_nh79g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kw8_nh79g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:navigation-filled" {...props}></Icon>
