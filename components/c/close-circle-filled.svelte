<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3w42fqxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j3w42fqxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:close-circle-filled" {...props}></Icon>
