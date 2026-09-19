<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk3tahbdx.css';
import '../../css/h/hh66d4b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uk3tahbdx"/><path class="hh66d4b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-heart-square" {...props}></Icon>
