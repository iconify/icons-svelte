<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfz9_616p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfz9_616p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clock-4-round" {...props}></Icon>
