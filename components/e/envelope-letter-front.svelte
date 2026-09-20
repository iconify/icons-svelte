<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkxnn-bnx.css';
import '../../css/v/vrxehybcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkxnn-bnx"/><path class="vrxehybcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:envelope-letter-front" {...props}></Icon>
