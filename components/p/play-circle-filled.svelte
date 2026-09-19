<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcch2tboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pcch2tboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:play-circle-filled" {...props}></Icon>
