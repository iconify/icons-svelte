<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buerymdqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="buerymdqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:folder-open-filled" {...props}></Icon>
