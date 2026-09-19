<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dky0zvbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dky0zvbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:box-plot-filled" {...props}></Icon>
