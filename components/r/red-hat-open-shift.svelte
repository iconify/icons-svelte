<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk3l2gykm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zk3l2gykm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:red-hat-open-shift" {...props}></Icon>
