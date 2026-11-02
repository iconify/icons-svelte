<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixx0vdzcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixx0vdzcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:middle-finger-line" {...props}></Icon>
