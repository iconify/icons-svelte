<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf5a1pvvg.css';
import '../../css/k/kgk49pb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wf5a1pvvg"/><path class="kgk49pb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folder-duotone-fill" {...props}></Icon>
