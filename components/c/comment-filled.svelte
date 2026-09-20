<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evo6idb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evo6idb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:comment-filled" {...props}></Icon>
