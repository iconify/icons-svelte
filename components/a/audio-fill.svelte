<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_s0f7s9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u_s0f7s9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:audio-fill" {...props}></Icon>
