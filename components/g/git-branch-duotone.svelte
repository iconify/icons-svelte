<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q74fwu1qf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary q74fwu1qf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:git-branch-duotone" {...props}></Icon>
