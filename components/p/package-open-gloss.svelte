<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv78kg08c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bv78kg08c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:package-open-gloss" {...props}></Icon>
