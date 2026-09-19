<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7ecjvb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x7ecjvb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:down-square-fill" {...props}></Icon>
