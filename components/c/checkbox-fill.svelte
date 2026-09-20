<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3fggeauu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z3fggeauu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:checkbox-fill" {...props}></Icon>
