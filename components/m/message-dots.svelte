<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncggv999k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncggv999k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:message-dots" {...props}></Icon>
