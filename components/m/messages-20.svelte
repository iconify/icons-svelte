<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2ik_bbaf.css';
import '../../css/i/idjsz7b6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t2ik_bbaf"/><path class="idjsz7b6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:messages-20" {...props}></Icon>
