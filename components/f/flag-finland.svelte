<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkq7-hbwz.css';
import '../../css/y/y6yyxt2hz.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="jkq7-hbwz"/><path class="y6yyxt2hz"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-finland" {...props}></Icon>
