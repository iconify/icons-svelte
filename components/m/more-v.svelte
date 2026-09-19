<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzvafrbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":5,"height":24};
const content = `<path class="zzvafrbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:more-v" {...props}></Icon>
