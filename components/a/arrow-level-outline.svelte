<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km523rbjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="km523rbjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-level-outline" {...props}></Icon>
