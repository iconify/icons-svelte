<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbx5wd37y.css';
import '../../css/u/u9ewtabjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bbx5wd37y"/><path class="u9ewtabjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:folder-open-twotone" {...props}></Icon>
