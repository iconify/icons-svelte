<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8dmqzbdr.css';
import '../../css/g/ge7idsbtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b8dmqzbdr"/><path class="ge7idsbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:notification-twotone" {...props}></Icon>
