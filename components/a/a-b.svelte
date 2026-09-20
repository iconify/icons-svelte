<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4kv38r6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4kv38r6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:a-b" {...props}></Icon>
