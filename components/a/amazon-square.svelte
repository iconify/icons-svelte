<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db8k76whz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="db8k76whz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:amazon-square" {...props}></Icon>
