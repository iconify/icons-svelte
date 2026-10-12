<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebvylcb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ebvylcb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:balloon-filled" {...props}></Icon>
