<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwt0w95mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwt0w95mp primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-terminator-duotone" {...props}></Icon>
