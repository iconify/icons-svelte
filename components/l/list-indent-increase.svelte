<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjop1kbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjop1kbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:list-indent-increase" {...props}></Icon>
