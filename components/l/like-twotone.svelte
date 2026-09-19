<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_esyy1fg.css';
import '../../css/q/q542tnbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e_esyy1fg"/><path class="q542tnbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:like-twotone" {...props}></Icon>
