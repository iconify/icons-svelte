<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hstsr7bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hstsr7bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:redo-outlined" {...props}></Icon>
