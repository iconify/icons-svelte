<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syfef3t7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="syfef3t7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:github-fill" {...props}></Icon>
