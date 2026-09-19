<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpf0ayjpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dpf0ayjpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-happy-beaming" {...props}></Icon>
