<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-voppbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r-voppbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:field-string" {...props}></Icon>
