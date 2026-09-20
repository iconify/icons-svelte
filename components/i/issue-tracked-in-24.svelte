<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaa3sjb5u.css';
import '../../css/t/t949fr4iy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uaa3sjb5u"/><path class="t949fr4iy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:issue-tracked-in-24" {...props}></Icon>
