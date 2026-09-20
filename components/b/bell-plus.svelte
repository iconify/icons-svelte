<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0ryyyv2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0ryyyv2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bell-plus" {...props}></Icon>
