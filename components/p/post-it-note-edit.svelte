<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j18_k-ber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j18_k-ber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:post-it-note-edit" {...props}></Icon>
