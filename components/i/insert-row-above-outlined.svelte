<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g596w6bde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g596w6bde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:insert-row-above-outlined" {...props}></Icon>
