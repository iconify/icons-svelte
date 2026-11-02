<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt2xfwnfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tt2xfwnfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:brush-fill" {...props}></Icon>
