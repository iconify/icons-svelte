<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc5gtrarx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rc5gtrarx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:ai-skill" {...props}></Icon>
