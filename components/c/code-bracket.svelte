<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmri4piok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="lmri4piok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:code-bracket" {...props}></Icon>
