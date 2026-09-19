<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7kh2ac5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="s7kh2ac5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:folder-fill-badge-person-crop" {...props}></Icon>
