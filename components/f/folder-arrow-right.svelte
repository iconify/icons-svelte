<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd18jumlu.css';
import '../../css/l/ll5_hob1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd18jumlu"/><path clip-rule="evenodd" class="ll5_hob1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-arrow-right" {...props}></Icon>
