<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2v3pubwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2v3pubwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:broom-filled" {...props}></Icon>
