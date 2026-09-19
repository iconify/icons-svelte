<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5yi3v23j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c5yi3v23j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:gitlab-outlined" {...props}></Icon>
