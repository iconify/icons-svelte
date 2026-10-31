<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmotu810x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmotu810x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-warning-gloss" {...props}></Icon>
