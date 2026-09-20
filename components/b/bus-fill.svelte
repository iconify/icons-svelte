<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq4hmxb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aq4hmxb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bus-fill" {...props}></Icon>
