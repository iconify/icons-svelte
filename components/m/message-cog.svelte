<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9wjuxe-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9wjuxe-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-cog" {...props}></Icon>
