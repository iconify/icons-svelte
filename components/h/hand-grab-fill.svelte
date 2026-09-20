<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea-lfjlep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ea-lfjlep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hand-grab-fill" {...props}></Icon>
