<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh49r0egi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh49r0egi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:discord-fill" {...props}></Icon>
