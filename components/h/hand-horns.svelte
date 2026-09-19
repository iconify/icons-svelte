<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh-gn6b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="kh-gn6b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:hand-horns" {...props}></Icon>
