<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da4v1sb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="da4v1sb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:link-off" {...props}></Icon>
