<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge1denbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ge1denbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:more" {...props}></Icon>
