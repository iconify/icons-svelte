<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_r27j01j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":512};
const content = `<path clip-rule="evenodd" class="t_r27j01j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:keybase" {...props}></Icon>
