<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynxh_kl6a.css';
import '../../css/w/wboyqji3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynxh_kl6a"/><path class="wboyqji3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:messages-bubble-square-subtract-bold" {...props}></Icon>
