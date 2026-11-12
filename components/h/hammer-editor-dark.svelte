<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2v_2ib2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u2v_2ib2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hammer-editor-dark" {...props}></Icon>
