<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsiv3aben.css';
import '../../css/q/qta_1ibzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="tsiv3aben"/><path class="qta_1ibzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:black-small-square" {...props}></Icon>
