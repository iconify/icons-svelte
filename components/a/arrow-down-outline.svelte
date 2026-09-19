<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbf6h660b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbf6h660b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:arrow-down-outline" {...props}></Icon>
