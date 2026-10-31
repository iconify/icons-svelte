<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3xt6ccoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3xt6ccoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-double-left-fill-round" {...props}></Icon>
