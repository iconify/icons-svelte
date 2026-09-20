<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj6l9vbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kj6l9vbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:aurabal" {...props}></Icon>
