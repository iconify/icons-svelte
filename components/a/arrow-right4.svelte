<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el-_qkqtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="el-_qkqtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-right4" {...props}></Icon>
