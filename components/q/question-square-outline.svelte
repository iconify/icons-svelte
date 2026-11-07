<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmytes_jh.css';
import '../../css/x/x41xvfi0c.css';
import '../../css/z/z79g45bsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmytes_jh"/><path class="x41xvfi0c"/><path clip-rule="evenodd" class="z79g45bsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:question-square-outline" {...props}></Icon>
