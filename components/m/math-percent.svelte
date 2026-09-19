<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucwqhuc2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucwqhuc2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:math-percent" {...props}></Icon>
