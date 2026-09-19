<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5qqi8poj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="g5qqi8poj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-u-turn-outline" {...props}></Icon>
