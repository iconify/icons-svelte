<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd5dlbc_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jd5dlbc_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:file-blank" {...props}></Icon>
