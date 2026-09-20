<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyle9lbps.css';
import '../../css/a/amvusujsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wyle9lbps"/><path clip-rule="evenodd" class="amvusujsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cnht" {...props}></Icon>
