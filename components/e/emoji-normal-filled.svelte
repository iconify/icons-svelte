<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imk-gsbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imk-gsbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:emoji-normal-filled" {...props}></Icon>
