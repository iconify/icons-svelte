<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcxv7rblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcxv7rblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:globe-gloss" {...props}></Icon>
