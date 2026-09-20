<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2jo_5btr.css';
import '../../css/m/muf1bphxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="f2jo_5btr"/><path class="muf1bphxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:loading-3-fill" {...props}></Icon>
