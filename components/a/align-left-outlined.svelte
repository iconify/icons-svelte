<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvx42bbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fvx42bbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:align-left-outlined" {...props}></Icon>
