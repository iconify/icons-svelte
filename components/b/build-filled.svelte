<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neidi-lvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="neidi-lvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:build-filled" {...props}></Icon>
