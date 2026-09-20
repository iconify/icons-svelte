<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hisfu9s-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hisfu9s-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:corner-right-down" {...props}></Icon>
