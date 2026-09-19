<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4_uvrykv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b4_uvrykv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:link" {...props}></Icon>
