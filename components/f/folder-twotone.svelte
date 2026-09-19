<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s310mjyrf.css';
import '../../css/p/pvkzb2byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s310mjyrf"/><path class="pvkzb2byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:folder-twotone" {...props}></Icon>
