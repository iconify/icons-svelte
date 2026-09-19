<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1j49ptmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="y1j49ptmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-cyrillic" {...props}></Icon>
