<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abm5005hg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abm5005hg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:beer-fill-round" {...props}></Icon>
