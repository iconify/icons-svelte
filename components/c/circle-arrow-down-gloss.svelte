<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_emwb22v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_emwb22v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-arrow-down-gloss" {...props}></Icon>
