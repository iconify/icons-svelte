<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy5l4bcpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qy5l4bcpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cup-soda-gloss" {...props}></Icon>
