<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf1ldn2li.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xf1ldn2li"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:http-put-off" {...props}></Icon>
