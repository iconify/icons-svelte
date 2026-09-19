<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_p-fzb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="f_p-fzb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:jakefile" {...props}></Icon>
