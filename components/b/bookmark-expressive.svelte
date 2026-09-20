<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-kdhpfzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p-kdhpfzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:bookmark-expressive" {...props}></Icon>
