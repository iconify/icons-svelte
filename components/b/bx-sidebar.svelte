<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sslr2nb7i.css';
import '../../css/y/y36i_nbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sslr2nb7i"/><path class="y36i_nbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-sidebar" {...props}></Icon>
