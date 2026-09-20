<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjne4gbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjne4gbyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ripple" {...props}></Icon>
