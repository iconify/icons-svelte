<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iybzqqbxo.css';
import '../../css/g/g4708uo1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iybzqqbxo"/><path class="g4708uo1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:icicles-20" {...props}></Icon>
