<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f11os4btd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f11os4btd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:more-square-vert-line" {...props}></Icon>
