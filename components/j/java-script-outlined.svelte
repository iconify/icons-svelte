<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqh1l2nbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wqh1l2nbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:java-script-outlined" {...props}></Icon>
