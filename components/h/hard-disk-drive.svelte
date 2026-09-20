<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5kyyl9ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="v5kyyl9ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:hard-disk-drive" {...props}></Icon>
