<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azo4x4paw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="azo4x4paw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:archive-box-solid" {...props}></Icon>
