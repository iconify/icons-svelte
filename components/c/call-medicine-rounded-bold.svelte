<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/y9p_4kb4n.css';
import '../../css/m/mg6lbnbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y9p_4kb4n"/><path clip-rule="evenodd" class="mg6lbnbje"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:call-medicine-rounded-bold" {...props}></Icon>
