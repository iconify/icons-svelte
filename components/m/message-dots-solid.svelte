<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn2oh2b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qn2oh2b2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:message-dots-solid" {...props}></Icon>
