<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrgf5g66q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrgf5g66q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-91-small" {...props}></Icon>
