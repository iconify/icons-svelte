<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mflfgibau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="mflfgibau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:cloud" {...props}></Icon>
