<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec4-tcc7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ec4-tcc7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:headset" {...props}></Icon>
