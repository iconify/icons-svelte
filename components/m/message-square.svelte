<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s20yxy53u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s20yxy53u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:message-square" {...props}></Icon>
