<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3j60pb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p3j60pb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:capsule-fill" {...props}></Icon>
