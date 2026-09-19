<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5172_-am.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w5172_-am"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:perplexity-filled" {...props}></Icon>
