<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5vp10bfi.css';
import '../../css/k/k1vbm5bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer v5vp10bfi"/><path class="duoicon-primary-layer k1vbm5bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:calendar" {...props}></Icon>
