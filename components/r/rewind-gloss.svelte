<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkxxpyaul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkxxpyaul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:rewind-gloss" {...props}></Icon>
