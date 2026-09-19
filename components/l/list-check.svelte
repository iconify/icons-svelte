<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkicm5bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkicm5bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:list-check" {...props}></Icon>
