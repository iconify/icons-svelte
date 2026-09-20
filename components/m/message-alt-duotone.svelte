<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxayxvndo.css';
import '../../css/x/xfzudwcmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="nxayxvndo"/><path class="xfzudwcmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:message-alt-duotone" {...props}></Icon>
