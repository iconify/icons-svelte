<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujtm8gbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ujtm8gbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:function-outlined" {...props}></Icon>
