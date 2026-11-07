<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2nrf10bf.css';
import '../../css/w/waj24z7nm.css';
import '../../css/q/qv7m4ujqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2nrf10bf"/><path clip-rule="evenodd" class="waj24z7nm"/><path clip-rule="evenodd" class="qv7m4ujqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-zip-bold-duotone" {...props}></Icon>
