<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mziq_kboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mziq_kboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gameboy-filled" {...props}></Icon>
