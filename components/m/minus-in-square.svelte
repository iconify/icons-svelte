<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh_-7lbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zh_-7lbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:minus-in-square" {...props}></Icon>
