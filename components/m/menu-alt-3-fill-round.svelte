<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahowc3_6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahowc3_6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:menu-alt-3-fill-round" {...props}></Icon>
