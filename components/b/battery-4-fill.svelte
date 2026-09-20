<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsep7jb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsep7jb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:battery-4-fill" {...props}></Icon>
