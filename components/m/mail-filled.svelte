<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcs-u5b0a.css';
import '../../css/k/kf0teob-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xcs-u5b0a"/><path class="kf0teob-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mail-filled" {...props}></Icon>
