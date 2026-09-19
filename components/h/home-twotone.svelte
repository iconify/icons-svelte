<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz498ccmf.css';
import '../../css/z/z7-yybbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oz498ccmf"/><path class="z7-yybbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:home-twotone" {...props}></Icon>
