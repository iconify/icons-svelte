<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp_jspb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jp_jspb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:math-equal" {...props}></Icon>
