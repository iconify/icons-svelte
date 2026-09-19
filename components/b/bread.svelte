<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aevp-mb1f.css';
import '../../css/e/etbak1bhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aevp-mb1f duoicon-secondary-layer"/><path class="duoicon-primary-layer etbak1bhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:bread" {...props}></Icon>
