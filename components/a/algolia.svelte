<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sei1hna7r.css';
import '../../css/b/b2of3ebrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sei1hna7r"/><path class="b2of3ebrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:algolia" {...props}></Icon>
