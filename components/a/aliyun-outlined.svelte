<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp8jllb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hp8jllb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:aliyun-outlined" {...props}></Icon>
