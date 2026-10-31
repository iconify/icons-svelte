<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhtbqcc4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhtbqcc4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-chevron-up-fill-round" {...props}></Icon>
