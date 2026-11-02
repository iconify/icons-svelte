<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-xkv2b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-xkv2b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-12-fill" {...props}></Icon>
