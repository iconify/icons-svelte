<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpr1erb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fpr1erb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:plane" {...props}></Icon>
