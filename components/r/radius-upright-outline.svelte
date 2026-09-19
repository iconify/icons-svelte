<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktvmvts2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ktvmvts2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:radius-upright-outline" {...props}></Icon>
