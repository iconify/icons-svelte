<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duxx7icww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="duxx7icww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:headphones-outline" {...props}></Icon>
