<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3vs2hbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3vs2hbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:angle-double-up" {...props}></Icon>
