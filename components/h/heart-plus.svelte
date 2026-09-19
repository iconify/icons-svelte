<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yiemwqbmv.css';
import '../../css/k/k6k1t_68c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yiemwqbmv"/><path class="k6k1t_68c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:heart-plus" {...props}></Icon>
