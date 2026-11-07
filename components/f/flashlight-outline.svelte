<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvnmopbkw.css';
import '../../css/q/q0xe3qbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvnmopbkw"/><path clip-rule="evenodd" class="q0xe3qbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:flashlight-outline" {...props}></Icon>
