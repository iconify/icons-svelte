<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmrsz7b0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmrsz7b0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-19-small" {...props}></Icon>
