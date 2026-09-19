<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/copanis1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="copanis1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:question-circle-filled" {...props}></Icon>
