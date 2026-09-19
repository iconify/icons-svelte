<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7k-jo7nm.css';
import '../../css/o/obxzrfd7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="v7k-jo7nm"/><path class="obxzrfd7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:plus-outline" {...props}></Icon>
