<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8ucqjzyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="a8ucqjzyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:note" {...props}></Icon>
