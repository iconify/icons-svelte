<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooj2r_z4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ooj2r_z4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:caret-left-filled" {...props}></Icon>
