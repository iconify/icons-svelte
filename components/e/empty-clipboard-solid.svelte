<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzks0db6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nzks0db6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:empty-clipboard-solid" {...props}></Icon>
