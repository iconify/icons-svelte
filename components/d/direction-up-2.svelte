<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yepaq--qq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yepaq--qq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:direction-up-2" {...props}></Icon>
