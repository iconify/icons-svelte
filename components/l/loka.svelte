<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqlox3zgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqlox3zgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:loka" {...props}></Icon>
