<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n35slstzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n35slstzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:bulb-fill" {...props}></Icon>
