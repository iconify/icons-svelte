<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjmsf2bdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hjmsf2bdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pencil-paintbrush-outline" {...props}></Icon>
