<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5aa0tfys.css';
import '../../css/r/r1qak2b5n.css';
import '../../css/h/h8k7vyb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u5aa0tfys"/><path class="r1qak2b5n"/><path class="h8k7vyb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-sync-20" {...props}></Icon>
