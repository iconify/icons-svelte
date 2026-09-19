<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek3i1rb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ek3i1rb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:email-fast" {...props}></Icon>
