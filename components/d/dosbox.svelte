<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao-aiub9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ao-aiub9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:dosbox" {...props}></Icon>
