<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz7ztrvle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oz7ztrvle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:column-width-outlined" {...props}></Icon>
