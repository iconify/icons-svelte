<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2lie5bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2lie5bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:contact-gloss" {...props}></Icon>
