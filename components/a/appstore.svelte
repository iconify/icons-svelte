<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjoy21biv.css';
import '../../css/m/m126krlgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjoy21biv duoicon-secondary-layer"/><path class="duoicon-primary-layer m126krlgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:appstore" {...props}></Icon>
