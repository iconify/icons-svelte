<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi8skqb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qi8skqb1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:apple-fill" {...props}></Icon>
