<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4dkv4uhs.css';
import '../../css/j/j05r12o9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4dkv4uhs"/><path class="j05r12o9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:call-cancel-bold-duotone" {...props}></Icon>
