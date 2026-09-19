<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljaw0iz7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ljaw0iz7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:kubernetes-outlined" {...props}></Icon>
