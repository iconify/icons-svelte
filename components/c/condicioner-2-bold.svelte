<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itl92zjdi.css';
import '../../css/r/rtxfoabgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="itl92zjdi"/><path class="rtxfoabgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:condicioner-2-bold" {...props}></Icon>
