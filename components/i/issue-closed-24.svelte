<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5ra11bdp.css';
import '../../css/z/zj49idy7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5ra11bdp"/><path class="zj49idy7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:issue-closed-24" {...props}></Icon>
