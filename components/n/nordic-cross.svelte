<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcobbgmle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hcobbgmle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:nordic-cross" {...props}></Icon>
