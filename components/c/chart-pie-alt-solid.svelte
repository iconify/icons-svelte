<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzargkbqk.css';
import '../../css/f/f11z55kqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzargkbqk"/><path class="f11z55kqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:chart-pie-alt-solid" {...props}></Icon>
