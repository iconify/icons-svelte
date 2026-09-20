<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi4qhlvbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi4qhlvbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-multiple-2-meters" {...props}></Icon>
