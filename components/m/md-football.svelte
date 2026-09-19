<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htk6txb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="htk6txb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-football" {...props}></Icon>
