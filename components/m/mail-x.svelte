<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi84ie6ix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yi84ie6ix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:mail-x" {...props}></Icon>
