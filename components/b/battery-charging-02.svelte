<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yul2lzr6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yul2lzr6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:battery-charging-02" {...props}></Icon>
