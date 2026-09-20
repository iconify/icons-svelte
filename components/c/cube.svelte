<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx64ur8pu.css';
import '../../css/d/da2w1iter.css';
import '../../css/v/vvr7kxj9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hx64ur8pu"/><path class="da2w1iter"/><path class="vvr7kxj9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:cube" {...props}></Icon>
