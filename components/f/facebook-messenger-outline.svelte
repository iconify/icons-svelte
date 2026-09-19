<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtl61lbwj.css';
import '../../css/w/wckjfubqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtl61lbwj"/><path clip-rule="evenodd" class="wckjfubqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:facebook-messenger-outline" {...props}></Icon>
