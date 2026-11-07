<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j21lmxkpv.css';
import '../../css/z/zueniel6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j21lmxkpv"/><path clip-rule="evenodd" class="zueniel6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-right-open-outline" {...props}></Icon>
