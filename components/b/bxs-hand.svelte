<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kffpw8bqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kffpw8bqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-hand" {...props}></Icon>
