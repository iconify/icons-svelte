<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdb8knb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdb8knb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:cog" {...props}></Icon>
