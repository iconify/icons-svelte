<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5c--obwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5c--obwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:flag-triangle-fill-round" {...props}></Icon>
