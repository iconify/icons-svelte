<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg2am7bzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lg2am7bzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:meh-outline" {...props}></Icon>
