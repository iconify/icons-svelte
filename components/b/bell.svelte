<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezbfhcbuu.css';
import '../../css/a/a45l8jhyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer ezbfhcbuu"/><path class="a45l8jhyb duoicon-secondary-layer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:bell" {...props}></Icon>
