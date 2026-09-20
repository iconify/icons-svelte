<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as6u8f6hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="as6u8f6hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:puzzle" {...props}></Icon>
