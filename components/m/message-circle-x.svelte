<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7e9t3b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7e9t3b8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-circle-x" {...props}></Icon>
