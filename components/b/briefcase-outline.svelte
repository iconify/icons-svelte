<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmwg3mbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="bmwg3mbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:briefcase-outline" {...props}></Icon>
