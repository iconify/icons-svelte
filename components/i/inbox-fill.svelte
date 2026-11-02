<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0wxph3-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0wxph3-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:inbox-fill" {...props}></Icon>
