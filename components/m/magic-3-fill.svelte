<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g35dtkbae.css';
import '../../css/n/n7uvfrbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g35dtkbae"/><path class="n7uvfrbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:magic-3-fill" {...props}></Icon>
