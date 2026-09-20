<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk6089bek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="bk6089bek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:conversation-filled" {...props}></Icon>
