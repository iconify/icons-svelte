<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn86bubkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":487,"height":512};
const content = `<path class="cn86bubkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:pkgsrc" {...props}></Icon>
