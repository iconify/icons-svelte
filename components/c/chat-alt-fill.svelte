<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzty0rkrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dzty0rkrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:chat-alt-fill" {...props}></Icon>
