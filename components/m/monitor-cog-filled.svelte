<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wssuxnb5s.css';
import '../../css/h/h4-_8v1va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wssuxnb5s"/><path clip-rule="evenodd" class="h4-_8v1va"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:monitor-cog-filled" {...props}></Icon>
