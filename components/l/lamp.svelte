<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6-_cry7c.css';
import '../../css/m/mhc-lebus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer p6-_cry7c"/><path class="duoicon-secondary-layer mhc-lebus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:lamp" {...props}></Icon>
