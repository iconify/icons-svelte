<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trohwccmt.css';
import '../../css/e/eq354xb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="trohwccmt"/><path class="eq354xb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:aim" {...props}></Icon>
