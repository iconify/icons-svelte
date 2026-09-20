<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfguy432a.css';
import '../../css/n/nhu-fkbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfguy432a"/><path class="nhu-fkbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:flip-to-front-filled" {...props}></Icon>
