<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgiwjsz1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgiwjsz1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:call-outgoing-02" {...props}></Icon>
