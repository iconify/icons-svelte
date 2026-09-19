<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elmx5rbsv.css';
import '../../css/w/w893w9fet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="elmx5rbsv"/><path class="w893w9fet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:cloud-upload" {...props}></Icon>
