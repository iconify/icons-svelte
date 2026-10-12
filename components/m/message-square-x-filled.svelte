<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsgjjsj8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lsgjjsj8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-square-x-filled" {...props}></Icon>
