<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw87rsb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fw87rsb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:play-list-folder-solid" {...props}></Icon>
