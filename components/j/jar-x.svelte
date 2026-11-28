<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh7ko11ac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zh7ko11ac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:jar-x" {...props}></Icon>
