<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wic510bop.css';
import '../../css/d/dpjsw5bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer wic510bop"/><path class="dpjsw5bva duoicon-primary-layer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:info" {...props}></Icon>
