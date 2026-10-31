<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo4h3mbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo4h3mbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:phone-off-fill-round" {...props}></Icon>
