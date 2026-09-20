<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx-ivcb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bx-ivcb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:counter-fill" {...props}></Icon>
