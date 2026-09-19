<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm4e34bbn.css';
import '../../css/j/jab1lr5xd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xm4e34bbn"/><path class="jab1lr5xd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:beer" {...props}></Icon>
