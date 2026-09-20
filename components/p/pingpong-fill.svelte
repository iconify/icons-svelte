<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaj94ab-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aaj94ab-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pingpong-fill" {...props}></Icon>
