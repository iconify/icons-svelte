<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp4dl1b8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp4dl1b8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heart-plus-fill" {...props}></Icon>
