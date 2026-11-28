<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjqrov1fr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjqrov1fr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:book-audio-solid" {...props}></Icon>
