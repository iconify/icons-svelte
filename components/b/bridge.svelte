<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlnf44bvp.css';
import '../../css/n/nfe2dnbyj.css';
import '../../css/q/qx-gz1b8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer hlnf44bvp"/><path class="duoicon-secondary-layer nfe2dnbyj"/><path class="duoicon-primary-layer qx-gz1b8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:bridge" {...props}></Icon>
