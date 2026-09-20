<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-6-22fzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="x-6-22fzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:paste" {...props}></Icon>
