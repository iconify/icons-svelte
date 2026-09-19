<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r07gb5b7z.css';
import '../../css/k/kev4430ki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r07gb5b7z"/><path class="kev4430ki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-checkbox-minus" {...props}></Icon>
