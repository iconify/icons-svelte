<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbuco0-ab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kbuco0-ab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hourglass-outline" {...props}></Icon>
