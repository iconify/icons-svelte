<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbgmgpb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbgmgpb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clipboard-list" {...props}></Icon>
