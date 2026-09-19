<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2j61makx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="a2j61makx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:default" {...props}></Icon>
