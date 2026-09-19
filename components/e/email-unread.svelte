<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi_la0bqj.css';
import '../../css/v/vf3vx-b1v.css';
import '../../css/a/a1xbh8u7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="vi_la0bqj"/><path class="vf3vx-b1v"/><path class="a1xbh8u7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:email-unread" {...props}></Icon>
