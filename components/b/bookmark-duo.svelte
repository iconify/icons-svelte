<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a25g90ajj.css';
import '../../css/o/oa9edkb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a25g90ajj secondary"/><path class="oa9edkb7e primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bookmark-duo" {...props}></Icon>
