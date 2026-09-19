<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qszn1yc9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qszn1yc9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:icq" {...props}></Icon>
