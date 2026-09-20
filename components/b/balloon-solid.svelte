<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcb7gsb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fcb7gsb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:balloon-solid" {...props}></Icon>
