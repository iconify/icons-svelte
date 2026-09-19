<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3wbybuzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a3wbybuzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:check-square-fill" {...props}></Icon>
