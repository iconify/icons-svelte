<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncy1prbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ncy1prbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:caret-right-outlined" {...props}></Icon>
