<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb5fwjseb.css';
import '../../css/x/xpcye44-n.css';
import '../../css/k/kcxdw0blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lb5fwjseb"/><path class="xpcye44-n"/><path clip-rule="evenodd" class="kcxdw0blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:domi" {...props}></Icon>
