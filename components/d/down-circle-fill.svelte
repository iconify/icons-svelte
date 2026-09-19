<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-av-u1xr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f-av-u1xr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:down-circle-fill" {...props}></Icon>
