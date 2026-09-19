<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0tl3qq7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b0tl3qq7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:insurance-fill" {...props}></Icon>
