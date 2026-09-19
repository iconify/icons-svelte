<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwtp_-bzj.css';
import '../../css/h/h3mkp0b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer xwtp_-bzj"/><path class="duoicon-primary-layer h3mkp0b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:apple" {...props}></Icon>
