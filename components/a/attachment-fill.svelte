<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm2xfac0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vm2xfac0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:attachment-fill" {...props}></Icon>
