<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hueh19bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="hueh19bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:bookmark" {...props}></Icon>
