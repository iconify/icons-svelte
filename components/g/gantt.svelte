<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3g7w1yyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3g7w1yyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:gantt" {...props}></Icon>
