<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpyifib8k.css';
import '../../css/a/ay19o3lge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpyifib8k"/><path class="ay19o3lge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:phone-outgoing-filled" {...props}></Icon>
