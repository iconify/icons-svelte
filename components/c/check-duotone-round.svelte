<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld20vpmse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ld20vpmse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:check-duotone-round" {...props}></Icon>
