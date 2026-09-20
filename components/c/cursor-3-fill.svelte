<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-0pb5juk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d-0pb5juk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cursor-3-fill" {...props}></Icon>
