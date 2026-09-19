<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz16spphp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gz16spphp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:merge-filled" {...props}></Icon>
