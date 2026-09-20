<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0kzsac-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0kzsac-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:message-square-share" {...props}></Icon>
