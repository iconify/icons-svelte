<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udvq7hbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udvq7hbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ear-scan" {...props}></Icon>
