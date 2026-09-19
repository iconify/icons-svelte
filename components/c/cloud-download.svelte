<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5asd1mya.css';
import '../../css/w/w893w9fet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z5asd1mya"/><path class="w893w9fet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:cloud-download" {...props}></Icon>
