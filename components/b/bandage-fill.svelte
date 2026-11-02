<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax9-xtuce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax9-xtuce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bandage-fill" {...props}></Icon>
