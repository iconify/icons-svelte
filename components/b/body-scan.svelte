<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1_hb8b8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1_hb8b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:body-scan" {...props}></Icon>
