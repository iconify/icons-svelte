<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmsdlybyh.css';
import '../../css/u/ulimznb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tmsdlybyh"/><path class="ulimznb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:present-solid" {...props}></Icon>
