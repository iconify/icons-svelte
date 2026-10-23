<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7p1-ck8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7p1-ck8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:binary" {...props}></Icon>
