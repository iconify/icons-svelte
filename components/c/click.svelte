<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj2dy6ioy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="yj2dy6ioy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:click" {...props}></Icon>
