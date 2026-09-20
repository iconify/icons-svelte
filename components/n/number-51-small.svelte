<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixpidxb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixpidxb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-51-small" {...props}></Icon>
