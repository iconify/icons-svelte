<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9uk8bgdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="m9uk8bgdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:reconciliation-filled" {...props}></Icon>
