<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2pg9jc9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2pg9jc9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:eyedropper" {...props}></Icon>
