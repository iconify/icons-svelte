<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlv74gbrp.css';
import '../../css/s/snocxdbcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rlv74gbrp"/><path class="snocxdbcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:notes-tasks-bold" {...props}></Icon>
