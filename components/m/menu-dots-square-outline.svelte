<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocavnt7jz.css';
import '../../css/k/kkhl62fff.css';
import '../../css/o/o-v99zb0r.css';
import '../../css/g/g4e643m4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocavnt7jz"/><path class="kkhl62fff"/><path class="o-v99zb0r"/><path clip-rule="evenodd" class="g4e643m4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:menu-dots-square-outline" {...props}></Icon>
