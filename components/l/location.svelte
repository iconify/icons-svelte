<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex619chfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ex619chfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:location" {...props}></Icon>
