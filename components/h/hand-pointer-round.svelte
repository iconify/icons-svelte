<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lioqs3ybo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lioqs3ybo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hand-pointer-round" {...props}></Icon>
