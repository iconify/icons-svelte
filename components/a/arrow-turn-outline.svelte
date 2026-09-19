<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz4fgyl6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="gz4fgyl6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-turn-outline" {...props}></Icon>
