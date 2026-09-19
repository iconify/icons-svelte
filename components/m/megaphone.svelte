<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us_otrb6w.css';
import '../../css/o/osmzo-b7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="us_otrb6w"/><path class="osmzo-b7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:megaphone" {...props}></Icon>
